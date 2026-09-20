<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrb6h1bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrb6h1bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:injective" /></template>
