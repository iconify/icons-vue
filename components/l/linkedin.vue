<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8782qb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m8782qb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:linkedin" /></template>
