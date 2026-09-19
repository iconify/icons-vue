<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drxyx7dbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drxyx7dbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bell-on" /></template>
