<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd9qbabfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jd9qbabfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrows-long-h" /></template>
