<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p63splqok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p63splqok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:add" /></template>
