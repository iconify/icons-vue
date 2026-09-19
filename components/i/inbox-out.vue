<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md585jgiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md585jgiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:inbox-out" /></template>
