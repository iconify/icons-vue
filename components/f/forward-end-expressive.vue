<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_39r13ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_39r13ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:forward-end-expressive" /></template>
