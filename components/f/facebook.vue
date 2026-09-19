<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofy1pmhsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofy1pmhsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:facebook" /></template>
