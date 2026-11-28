<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohjgf69hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohjgf69hh primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:expand-sparkles-duotone" /></template>
