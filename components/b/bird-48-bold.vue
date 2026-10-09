<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isno3kbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="isno3kbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bird-48-bold" /></template>
