<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-fv5ok9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c-fv5ok9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal" /></template>
