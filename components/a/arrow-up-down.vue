<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyyg_11vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tyyg_11vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-up-down" /></template>
