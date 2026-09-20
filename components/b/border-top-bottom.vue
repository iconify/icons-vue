<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh7hngbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rh7hngbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-top-bottom" /></template>
