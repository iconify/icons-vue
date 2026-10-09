<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ps03s-o.css';
import '../../css/i/iz1dmwoac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y9ps03s-o"/><path class="iz1dmwoac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:invoice-20-bold" /></template>
