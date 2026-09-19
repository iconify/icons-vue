<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5p-6bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ke5p-6bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:bimobject" /></template>
