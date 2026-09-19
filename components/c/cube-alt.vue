<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0a8gi0lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a8gi0lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cube-alt" /></template>
