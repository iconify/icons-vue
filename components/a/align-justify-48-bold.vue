<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzbesmblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzbesmblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-justify-48-bold" /></template>
