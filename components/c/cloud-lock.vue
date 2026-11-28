<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbguf92ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbguf92ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-lock" /></template>
