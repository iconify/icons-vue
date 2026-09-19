<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp3kewbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp3kewbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:cloud" /></template>
