<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfg_0dbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tfg_0dbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:jinja-light" /></template>
