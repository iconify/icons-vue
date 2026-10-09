<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_918vwrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_918vwrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-right-48-bold" /></template>
