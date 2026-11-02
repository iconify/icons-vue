<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-hcm6bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-hcm6bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bug-play-fill" /></template>
