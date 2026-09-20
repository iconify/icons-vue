<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2zc3_bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="y2zc3_bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:eject-circle" /></template>
