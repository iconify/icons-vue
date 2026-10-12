<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss0igbcet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ss0igbcet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hail-48-bold" /></template>
