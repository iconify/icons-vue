<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz1n53-_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz1n53-_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:equal-not" /></template>
