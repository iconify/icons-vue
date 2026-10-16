<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb9sfrenb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":91,"height":43};
const content = `<path class="nb9sfrenb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:infisical-light" /></template>
