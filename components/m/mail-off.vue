<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq_593bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq_593bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-off" /></template>
