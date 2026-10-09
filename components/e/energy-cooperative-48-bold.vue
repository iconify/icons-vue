<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlolk7bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hlolk7bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-cooperative-48-bold" /></template>
