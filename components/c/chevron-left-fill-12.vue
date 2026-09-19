<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqaugudbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oqaugudbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-left-fill-12" /></template>
