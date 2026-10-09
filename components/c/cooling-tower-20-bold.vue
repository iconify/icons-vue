<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6z7-hvpd.css';
import '../../css/m/ms-gp00fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a6z7-hvpd"/><path class="ms-gp00fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooling-tower-20-bold" /></template>
