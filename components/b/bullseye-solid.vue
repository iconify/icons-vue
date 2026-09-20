<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmi96sb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pmi96sb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bullseye-solid" /></template>
