<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-5pybak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="g8-5pybak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:lock-open" /></template>
