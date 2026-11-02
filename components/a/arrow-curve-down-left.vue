<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh7vxndfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh7vxndfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-left" /></template>
