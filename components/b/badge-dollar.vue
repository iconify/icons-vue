<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7fgw7bls.css';
import '../../css/y/yua1kc2gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7fgw7bls"/><path class="yua1kc2gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:badge-dollar" /></template>
