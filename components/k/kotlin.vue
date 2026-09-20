<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl51yfbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl51yfbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:kotlin" /></template>
