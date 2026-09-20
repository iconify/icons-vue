<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5iwp7g-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z5iwp7g-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checkbox-blank" /></template>
