<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc9_1yu8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oc9_1yu8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-reverse-stroke-12" /></template>
