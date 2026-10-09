<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_okms-zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_okms-zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blackout-48-bold" /></template>
