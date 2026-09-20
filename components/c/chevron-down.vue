<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd0piybon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bd0piybon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-down" /></template>
