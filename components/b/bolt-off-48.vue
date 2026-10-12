<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzbdracbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uzbdracbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-off-48" /></template>
