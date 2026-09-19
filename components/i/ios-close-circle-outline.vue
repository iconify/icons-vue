<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3iqr-btu.css';
import '../../css/l/lalksfbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3iqr-btu"/><path class="lalksfbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-close-circle-outline" /></template>
