<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkhog23kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkhog23kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dot-arrow-right" /></template>
