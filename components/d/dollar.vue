<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmvr5l_be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmvr5l_be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dollar" /></template>
