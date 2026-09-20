<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmdkf4bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdkf4bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ceiling-lamp-multiple" /></template>
