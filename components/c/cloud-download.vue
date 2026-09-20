<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-zt9rbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-zt9rbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-download" /></template>
