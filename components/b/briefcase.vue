<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh6t7r4um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fh6t7r4um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:briefcase" /></template>
