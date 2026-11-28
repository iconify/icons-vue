<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0zbl7bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0zbl7bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:face-frown" /></template>
