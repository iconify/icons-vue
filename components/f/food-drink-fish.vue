<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn_mdboia.css';
import '../../css/k/k78ldxeyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nn_mdboia"/><path class="k78ldxeyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-fish" /></template>
