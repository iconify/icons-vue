<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5z5j8bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h5z5j8bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-left-20-solid" /></template>
