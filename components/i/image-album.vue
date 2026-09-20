<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iua635beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iua635beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-album" /></template>
