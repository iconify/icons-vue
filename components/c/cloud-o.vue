<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9z9i0-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9z9i0-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cloud-o" /></template>
