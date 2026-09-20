<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fev6zvamb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fev6zvamb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dot-fill-16" /></template>
