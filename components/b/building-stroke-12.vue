<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa-t1nyfw.css';
import '../../css/z/zjegb3bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xa-t1nyfw"/><path class="zjegb3bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:building-stroke-12" /></template>
