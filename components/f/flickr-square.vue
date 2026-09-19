<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqw5sgesf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqw5sgesf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:flickr-square" /></template>
