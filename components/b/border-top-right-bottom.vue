<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkte9o6es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rkte9o6es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-top-right-bottom" /></template>
