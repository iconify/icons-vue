<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtybyow4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dtybyow4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:headphones" /></template>
