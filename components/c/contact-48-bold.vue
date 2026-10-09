<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_yowkbgo.css';
import '../../css/f/fdc56liyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_yowkbgo"/><path class="fdc56liyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contact-48-bold" /></template>
