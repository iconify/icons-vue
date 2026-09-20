<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpmof_b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jpmof_b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-down-right" /></template>
