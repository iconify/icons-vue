<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q54ebz0wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q54ebz0wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:credits" /></template>
