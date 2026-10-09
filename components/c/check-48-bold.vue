<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fko3tyrmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fko3tyrmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-48-bold" /></template>
