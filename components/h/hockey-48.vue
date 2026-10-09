<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igrsxkh2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="igrsxkh2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hockey-48" /></template>
