<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3n0ufbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3n0ufbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dashboard-plus" /></template>
