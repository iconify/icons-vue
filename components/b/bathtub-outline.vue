<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd6l2pibj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd6l2pibj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bathtub-outline" /></template>
