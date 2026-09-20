<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6kqtwjhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6kqtwjhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-multiple" /></template>
