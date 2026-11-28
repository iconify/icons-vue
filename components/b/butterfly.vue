<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjv1czb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjv1czb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:butterfly" /></template>
