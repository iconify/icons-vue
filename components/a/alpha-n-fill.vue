<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bosfi5b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bosfi5b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-n-fill" /></template>
