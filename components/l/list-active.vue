<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlp8g_b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlp8g_b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:list-active" /></template>
