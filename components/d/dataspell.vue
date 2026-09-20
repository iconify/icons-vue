<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1adf7z0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f1adf7z0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dataspell" /></template>
