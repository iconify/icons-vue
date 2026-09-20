<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shzgw1b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shzgw1b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-play-outline" /></template>
