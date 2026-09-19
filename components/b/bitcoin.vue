<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtvztsq6v.css';
import '../../css/u/ul66odbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtvztsq6v"/><path class="ul66odbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bitcoin" /></template>
