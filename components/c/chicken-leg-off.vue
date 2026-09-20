<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg7dov6vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg7dov6vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chicken-leg-off" /></template>
