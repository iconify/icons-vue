<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcjd4sbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcjd4sbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flame-duotone" /></template>
