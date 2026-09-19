<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zurw434pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="zurw434pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:first-order" /></template>
