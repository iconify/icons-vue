<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lalksfbhk.css';
import '../../css/c/cesl7tgnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lalksfbhk"/><path class="cesl7tgnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-radio-button-on" /></template>
