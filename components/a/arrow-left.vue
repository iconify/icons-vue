<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozmh9abjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ozmh9abjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:arrow-left" /></template>
