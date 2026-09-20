<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-pxf5beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d-pxf5beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:communications-tower" /></template>
