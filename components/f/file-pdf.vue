<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5mlk4bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="f5mlk4bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-pdf" /></template>
