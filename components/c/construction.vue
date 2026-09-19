<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhjen_f9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":832};
const content = `<path class="uhjen_f9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:construction" /></template>
