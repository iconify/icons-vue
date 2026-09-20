<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob3y1iinc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ob3y1iinc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ellipsis-v" /></template>
