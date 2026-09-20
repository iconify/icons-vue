<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk5cg1pag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yk5cg1pag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:fitness" /></template>
