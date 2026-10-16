<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw6oy3bzc.css';
import '../../css/m/m-5n_6hvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw6oy3bzc"/><path class="m-5n_6hvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-reel-48-bold" /></template>
