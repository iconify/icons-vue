<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihi_ub2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yihi_ub2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-3-square-light" /></template>
