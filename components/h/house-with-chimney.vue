<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9mozs6lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d9mozs6lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:house-with-chimney" /></template>
