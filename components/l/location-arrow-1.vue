<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-idbj9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur-idbj9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:location-arrow-1" /></template>
