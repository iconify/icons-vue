<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsvmt9l8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zsvmt9l8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linecap-square-outline" /></template>
