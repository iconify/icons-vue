<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah2m33b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2m33b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-left-outline" /></template>
