<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg8r48zoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dg8r48zoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:code" /></template>
