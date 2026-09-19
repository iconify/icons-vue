<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lalksfbhk.css';
import '../../css/c/cx4edcbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lalksfbhk"/><path class="cx4edcbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-help-circle-outline" /></template>
