<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvywd9rkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvywd9rkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:closed-captioning" /></template>
