<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h61y6nb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h61y6nb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-hail-48-bold" /></template>
