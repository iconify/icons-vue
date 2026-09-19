<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot5cy7qnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ot5cy7qnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-increase-stroke-12" /></template>
