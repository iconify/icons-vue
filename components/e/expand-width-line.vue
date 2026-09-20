<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaxyglb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaxyglb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-width-line" /></template>
