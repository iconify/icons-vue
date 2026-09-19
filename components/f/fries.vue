<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd9m8rbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd9m8rbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:fries" /></template>
