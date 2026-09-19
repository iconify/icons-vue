<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdib-abbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdib-abbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-left" /></template>
