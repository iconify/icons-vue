<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-wj5bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ya-wj5bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:axe" /></template>
