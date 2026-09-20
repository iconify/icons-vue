<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmg_dlonm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmg_dlonm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-2-filled" /></template>
