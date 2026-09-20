<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fibqiob8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fibqiob8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left-bold-box-outline" /></template>
