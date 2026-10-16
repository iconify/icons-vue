<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t484tzbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t484tzbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:centrifuge-48-bold" /></template>
