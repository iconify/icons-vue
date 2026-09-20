<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw9qkp9ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw9qkp9ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-star-outline" /></template>
