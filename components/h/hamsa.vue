<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7es-7bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7es-7bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hamsa" /></template>
