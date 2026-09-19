<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilakvvs7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ilakvvs7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:building-circle-arrow-right" /></template>
