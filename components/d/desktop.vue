<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjxex1bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjxex1bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:desktop" /></template>
