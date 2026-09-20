<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycnkerkab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycnkerkab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:info" /></template>
