<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dusxnnqvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dusxnnqvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gnuplot" /></template>
