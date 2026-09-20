<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deoeijbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="deoeijbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:align-left-16" /></template>
