<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afu2d_v6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afu2d_v6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bezier" /></template>
