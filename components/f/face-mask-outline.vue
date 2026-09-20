<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_4g82bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_4g82bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:face-mask-outline" /></template>
