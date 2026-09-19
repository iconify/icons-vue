<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk4_gdckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fk4_gdckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-showers-heavy" /></template>
