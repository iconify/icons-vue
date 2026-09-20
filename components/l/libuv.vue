<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi4my1vub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi4my1vub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:libuv" /></template>
