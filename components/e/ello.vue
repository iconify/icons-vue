<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7-on_vwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i7-on_vwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ello" /></template>
