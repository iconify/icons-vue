<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djdd0mbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djdd0mbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-rain" /></template>
