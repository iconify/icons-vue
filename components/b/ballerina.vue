<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-b_-ietm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-b_-ietm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ballerina" /></template>
