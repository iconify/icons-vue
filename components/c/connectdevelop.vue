<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw98ts_6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zw98ts_6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:connectdevelop" /></template>
