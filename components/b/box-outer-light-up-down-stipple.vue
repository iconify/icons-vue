<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jie5rdb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jie5rdb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-down-stipple" /></template>
