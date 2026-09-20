<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggrkf1b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggrkf1b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contract-fill" /></template>
