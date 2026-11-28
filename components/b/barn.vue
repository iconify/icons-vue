<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub2g8ac3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub2g8ac3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:barn" /></template>
