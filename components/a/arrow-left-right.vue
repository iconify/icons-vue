<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et0g50bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="et0g50bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-left-right" /></template>
