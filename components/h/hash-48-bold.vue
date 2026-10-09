<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbl-5-buj.css';
import '../../css/v/v101e1bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbl-5-buj"/><path class="v101e1bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hash-48-bold" /></template>
