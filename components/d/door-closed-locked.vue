<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-4x6qhpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-4x6qhpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:door-closed-locked" /></template>
