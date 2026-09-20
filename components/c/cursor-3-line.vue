<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3tyt4bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3tyt4bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-3-line" /></template>
