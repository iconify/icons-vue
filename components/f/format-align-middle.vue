<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-7wgrhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da-7wgrhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-align-middle" /></template>
