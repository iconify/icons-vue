<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek81er-1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ek81er-1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:ice-cream-round" /></template>
