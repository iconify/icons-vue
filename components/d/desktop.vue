<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csqqi25wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="csqqi25wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:desktop" /></template>
