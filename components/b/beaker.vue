<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2iyfrbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j2iyfrbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:beaker" /></template>
