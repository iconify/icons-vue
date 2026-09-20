<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwdo5clsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uwdo5clsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bee-skep" /></template>
