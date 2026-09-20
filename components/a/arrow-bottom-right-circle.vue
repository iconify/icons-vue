<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2o0yeblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w2o0yeblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-bottom-right-circle" /></template>
