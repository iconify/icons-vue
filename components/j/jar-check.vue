<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw3pl2qrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw3pl2qrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:jar-check" /></template>
