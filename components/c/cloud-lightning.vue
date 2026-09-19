<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv8dteuwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8dteuwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-lightning" /></template>
