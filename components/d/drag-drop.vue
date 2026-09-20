<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1m__bn8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="k1m__bn8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:drag-drop" /></template>
