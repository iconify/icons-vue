<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz0aanbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz0aanbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-bald-gloss" /></template>
