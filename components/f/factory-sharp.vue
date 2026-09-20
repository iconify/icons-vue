<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncwy8z9pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwy8z9pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:factory-sharp" /></template>
