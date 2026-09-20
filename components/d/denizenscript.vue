<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn37rnbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jn37rnbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:denizenscript" /></template>
