<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1qa-m9-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m1qa-m9-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hpp" /></template>
