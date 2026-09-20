<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4994ssvl.css';
import '../../css/m/m5h3s7x3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d4994ssvl"/><path class="m5h3s7x3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:download" /></template>
