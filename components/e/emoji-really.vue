<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hro-8ebhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hro-8ebhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:emoji-really" /></template>
