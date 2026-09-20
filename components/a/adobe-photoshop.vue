<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fonifab6t.css';
import '../../css/q/qpkq3pbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="fonifab6t"/><path class="qpkq3pbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:adobe-photoshop" /></template>
