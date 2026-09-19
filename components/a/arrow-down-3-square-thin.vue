<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo1_vnkyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo1_vnkyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-3-square-thin" /></template>
