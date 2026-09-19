<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eev09qb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="eev09qb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:chevron-right" /></template>
