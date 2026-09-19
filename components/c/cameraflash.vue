<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcncdub3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="tcncdub3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cameraflash" /></template>
