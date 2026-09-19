<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3d1-5b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3d1-5b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-remove" /></template>
