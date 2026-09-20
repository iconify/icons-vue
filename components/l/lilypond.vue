<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en1zvri8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="en1zvri8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:lilypond" /></template>
