<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khm7x6mgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khm7x6mgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:language" /></template>
