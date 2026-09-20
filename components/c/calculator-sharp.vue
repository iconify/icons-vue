<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r25u83b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r25u83b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calculator-sharp" /></template>
