<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mar1fqi3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mar1fqi3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:area-search" /></template>
