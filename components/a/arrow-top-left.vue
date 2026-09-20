<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/con_4y89t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="con_4y89t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-top-left" /></template>
