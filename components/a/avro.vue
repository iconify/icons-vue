<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1b65dbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1b65dbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:avro" /></template>
