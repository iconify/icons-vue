<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct65k2brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct65k2brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calculator-variant" /></template>
