<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk7rcacre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uk7rcacre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-nuclear-energy" /></template>
