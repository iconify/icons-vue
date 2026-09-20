<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7r42cb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d7r42cb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:institution" /></template>
