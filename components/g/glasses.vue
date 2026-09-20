<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjd9lhbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sjd9lhbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:glasses" /></template>
