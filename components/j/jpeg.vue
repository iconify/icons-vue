<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdpq3-2hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdpq3-2hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jpeg" /></template>
