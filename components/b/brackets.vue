<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg0c3ac1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg0c3ac1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:brackets" /></template>
