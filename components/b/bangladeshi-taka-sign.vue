<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyv1v8bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="pyv1v8bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bangladeshi-taka-sign" /></template>
