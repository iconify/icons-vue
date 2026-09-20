<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9hp9pkuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k9hp9pkuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:abap" /></template>
