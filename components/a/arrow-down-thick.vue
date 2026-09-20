<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_j6oibjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_j6oibjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-thick" /></template>
