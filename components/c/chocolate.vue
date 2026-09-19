<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6gp9gbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6gp9gbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chocolate" /></template>
