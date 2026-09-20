<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynxtips6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ynxtips6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:h" /></template>
