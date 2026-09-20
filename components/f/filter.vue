<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqfi6ubqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gqfi6ubqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:filter" /></template>
