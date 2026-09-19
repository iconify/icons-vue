<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7pial3jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k7pial3jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dbc" /></template>
