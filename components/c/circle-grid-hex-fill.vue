<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j26yc11gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j26yc11gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:circle-grid-hex-fill" /></template>
