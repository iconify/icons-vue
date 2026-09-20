<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3ya7hera.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3ya7hera"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-break" /></template>
