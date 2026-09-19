<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru-ryy-1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru-ryy-1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gatsby" /></template>
