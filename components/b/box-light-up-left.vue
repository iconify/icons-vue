<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyi5-4gvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pyi5-4gvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-left" /></template>
