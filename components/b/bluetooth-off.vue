<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aktvk-bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aktvk-bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bluetooth-off" /></template>
