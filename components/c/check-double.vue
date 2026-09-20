<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii2_dhbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2_dhbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:check-double" /></template>
