<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erh8ajbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erh8ajbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:clapperboard-sharp" /></template>
