<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrt-b3b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrt-b3b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-plus" /></template>
