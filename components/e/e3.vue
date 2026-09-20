<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yid9b7myf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yid9b7myf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:e3" /></template>
