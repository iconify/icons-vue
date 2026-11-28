<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9an_9pbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9an_9pbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:infinity" /></template>
