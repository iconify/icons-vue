<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftlaln56r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ftlaln56r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:compsition-horizontal-flat" /></template>
