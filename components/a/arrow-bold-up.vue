<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6u6u_bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f6u6u_bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-bold-up" /></template>
