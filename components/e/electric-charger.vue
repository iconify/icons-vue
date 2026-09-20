<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjzirvbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjzirvbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electric-charger" /></template>
