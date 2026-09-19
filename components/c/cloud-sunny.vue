<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gli2wduus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gli2wduus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cloud-sunny" /></template>
