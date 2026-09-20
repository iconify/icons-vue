<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8q0zdbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c8q0zdbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-round-up-right" /></template>
