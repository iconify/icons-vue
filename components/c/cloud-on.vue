<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr4d2z28y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr4d2z28y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:cloud-on" /></template>
