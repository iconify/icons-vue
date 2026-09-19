<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsqv8iz_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wsqv8iz_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arrow-up" /></template>
