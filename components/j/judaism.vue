<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcnwy08sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcnwy08sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:judaism" /></template>
