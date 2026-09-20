<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-sa2uayq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n-sa2uayq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bell-o" /></template>
