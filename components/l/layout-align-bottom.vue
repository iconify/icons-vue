<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv1oty2ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv1oty2ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-align-bottom" /></template>
