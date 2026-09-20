<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs8w4nihw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs8w4nihw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-down-outline" /></template>
