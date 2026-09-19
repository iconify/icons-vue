<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xas62ub0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xas62ub0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:file-on" /></template>
