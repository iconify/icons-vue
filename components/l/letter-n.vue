<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzq-v8b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzq-v8b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-n" /></template>
