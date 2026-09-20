<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6bzm23k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg6bzm23k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluent-reader-dark" /></template>
