<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohrnlbcwc.css';
import '../../css/z/zxdaapb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ohrnlbcwc"/><path class="zxdaapb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:crosshairs-16" /></template>
