<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da_xu-bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_xu-bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:blender" /></template>
