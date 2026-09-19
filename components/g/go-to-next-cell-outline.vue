<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fynt03bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fynt03bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:go-to-next-cell-outline" /></template>
