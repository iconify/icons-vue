<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmylqvzxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmylqvzxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-h-box-outline" /></template>
