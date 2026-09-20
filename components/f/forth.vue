<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evjmnccgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":67.733,"height":67.733};
const content = `<path class="evjmnccgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:forth" /></template>
