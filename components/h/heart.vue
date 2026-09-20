<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr1zc8bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jr1zc8bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:heart" /></template>
