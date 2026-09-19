<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9o2i1oac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="x9o2i1oac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:circle" /></template>
