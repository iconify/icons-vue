<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbzronb6t.css';
import '../../css/d/dok_l2b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hbzronb6t"/><path class="dok_l2b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chalkboard-48-bold" /></template>
