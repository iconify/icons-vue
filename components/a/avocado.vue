<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uppb44qmx.css';
import '../../css/b/bmbc7qb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uppb44qmx"/><ellipse class="bmbc7qb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:avocado" /></template>
