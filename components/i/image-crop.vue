<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kasr6-q8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kasr6-q8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-crop" /></template>
