<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6bmebc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="n6bmebc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-left-stipple-outer" /></template>
