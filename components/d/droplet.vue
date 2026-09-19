<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg4mkfdxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg4mkfdxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:droplet" /></template>
