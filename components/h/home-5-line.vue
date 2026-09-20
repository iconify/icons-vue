<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tteo7nbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tteo7nbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-5-line" /></template>
