<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va3vigmkv.css';
import '../../css/q/qsn33xeca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="va3vigmkv"/><path class="qsn33xeca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-astro" /></template>
