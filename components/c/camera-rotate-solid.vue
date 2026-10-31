<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_3k02bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_3k02bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:camera-rotate-solid" /></template>
