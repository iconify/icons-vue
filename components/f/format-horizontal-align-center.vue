<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6mu9gbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="p6mu9gbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-horizontal-align-center" /></template>
