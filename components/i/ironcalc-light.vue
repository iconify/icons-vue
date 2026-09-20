<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f00tbez2j.css';
import '../../css/e/erolj7bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f00tbez2j"/><path class="erolj7bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironcalc-light" /></template>
