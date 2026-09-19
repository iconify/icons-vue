<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpfj5ub0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mpfj5ub0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:docbook" /></template>
