<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbl41hxck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbl41hxck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earth" /></template>
