<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikf5vpbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikf5vpbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bell-off" /></template>
