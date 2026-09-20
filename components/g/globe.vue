<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmiy7m5fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hmiy7m5fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:globe" /></template>
