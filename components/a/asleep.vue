<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7i9mubje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y7i9mubje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asleep" /></template>
