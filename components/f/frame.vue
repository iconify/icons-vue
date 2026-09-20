<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngex8nbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngex8nbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:frame" /></template>
