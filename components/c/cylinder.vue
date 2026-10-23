<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbtj98ggr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbtj98ggr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cylinder" /></template>
