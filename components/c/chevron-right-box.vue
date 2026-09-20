<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz9m3nbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz9m3nbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-right-box" /></template>
