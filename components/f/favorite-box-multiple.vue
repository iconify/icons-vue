<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-qr3i-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-qr3i-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-box-multiple" /></template>
