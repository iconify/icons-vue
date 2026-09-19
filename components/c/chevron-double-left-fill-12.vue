<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do1xd6lny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="do1xd6lny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-left-fill-12" /></template>
