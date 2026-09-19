<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/samxp0zez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="samxp0zez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-down-square" /></template>
