<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-e5hhbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t-e5hhbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:latexmk" /></template>
