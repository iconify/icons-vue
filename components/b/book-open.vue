<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o41f9fxfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="o41f9fxfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:book-open" /></template>
