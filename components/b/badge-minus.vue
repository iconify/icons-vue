<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c399ppbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c399ppbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-minus" /></template>
