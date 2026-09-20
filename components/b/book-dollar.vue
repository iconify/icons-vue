<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcbirc5ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcbirc5ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:book-dollar" /></template>
