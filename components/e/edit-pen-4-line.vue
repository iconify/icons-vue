<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7xh53b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7xh53b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:edit-pen-4-line" /></template>
