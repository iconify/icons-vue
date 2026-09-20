<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7hsp1bfr.css';
import '../../css/b/bn2tkibzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7hsp1bfr"/><path class="bn2tkibzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ieth" /></template>
