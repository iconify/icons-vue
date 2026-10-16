<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn90sxb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hn90sxb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:focus-48-bold" /></template>
