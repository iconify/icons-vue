<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a230-oeew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a230-oeew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:4g" /></template>
