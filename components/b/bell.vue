<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiorso2ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiorso2ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bell" /></template>
