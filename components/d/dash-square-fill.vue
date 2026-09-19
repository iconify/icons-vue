<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugaiacrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hugaiacrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dash-square-fill" /></template>
