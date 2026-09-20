<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzfyu8bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jzfyu8bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-u-fill" /></template>
