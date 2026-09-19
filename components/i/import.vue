<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq0busbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uq0busbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:import" /></template>
