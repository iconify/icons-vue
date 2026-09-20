<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1m-6qb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t1m-6qb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:door-closed" /></template>
