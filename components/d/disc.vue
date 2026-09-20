<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekjr1ib4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ekjr1ib4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:disc" /></template>
