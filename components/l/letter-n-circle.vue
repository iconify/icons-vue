<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvrgzacds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvrgzacds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-n-circle" /></template>
