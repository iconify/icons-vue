<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-kafac1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-kafac1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-pdf-outline" /></template>
