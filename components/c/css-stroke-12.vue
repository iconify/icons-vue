<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-cmxab5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d-cmxab5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:css-stroke-12" /></template>
