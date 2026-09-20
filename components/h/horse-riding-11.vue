<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ivvacuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="h_ivvacuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:horse-riding-11" /></template>
