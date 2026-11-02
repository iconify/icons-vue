<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-pj1xb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pj1xb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:announcement-line" /></template>
