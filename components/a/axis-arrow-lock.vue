<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkawrjb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkawrjb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-arrow-lock" /></template>
