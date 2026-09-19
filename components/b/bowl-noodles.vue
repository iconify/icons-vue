<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uteucv-lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uteucv-lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bowl-noodles" /></template>
