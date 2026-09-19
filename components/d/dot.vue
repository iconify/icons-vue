<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoe9-6brl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uoe9-6brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dot" /></template>
