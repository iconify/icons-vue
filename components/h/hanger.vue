<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_3jp4bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_3jp4bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hanger" /></template>
