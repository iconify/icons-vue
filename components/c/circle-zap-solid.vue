<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxfb3xbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfb3xbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-zap-solid" /></template>
