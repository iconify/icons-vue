<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upkt8ry-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="upkt8ry-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bell-slash-o" /></template>
