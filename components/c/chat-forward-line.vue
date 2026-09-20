<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfx6_cbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfx6_cbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-forward-line" /></template>
