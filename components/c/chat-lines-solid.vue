<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk2-5bcxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk2-5bcxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-lines-solid" /></template>
