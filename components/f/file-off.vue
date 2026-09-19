<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m80yhwbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m80yhwbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:file-off" /></template>
