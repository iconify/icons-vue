<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjawm7bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fjawm7bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-insights-dark" /></template>
