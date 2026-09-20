<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm644_2yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gm644_2yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up" /></template>
