<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cosz63sab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="cosz63sab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hotel" /></template>
