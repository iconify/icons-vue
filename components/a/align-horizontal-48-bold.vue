<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihieunbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihieunbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-horizontal-48-bold" /></template>
