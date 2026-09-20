<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydzbdhtcp.css';
import '../../css/e/e5c90cc_n.css';
import '../../css/m/md21q1b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":333.22,"height":333.22};
const content = `<path class="ydzbdhtcp"/><path class="e5c90cc_n"/><path class="md21q1b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dominos-dark" /></template>
