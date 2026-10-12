<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoulf2y9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uoulf2y9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hail-48" /></template>
