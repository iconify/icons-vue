<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st2be1bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="st2be1bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-down" /></template>
