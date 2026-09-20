<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7k4b0bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7k4b0bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-down" /></template>
