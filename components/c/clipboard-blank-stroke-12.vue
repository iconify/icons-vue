<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7saf9b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y7saf9b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-blank-stroke-12" /></template>
