<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f37262bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f37262bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:database" /></template>
