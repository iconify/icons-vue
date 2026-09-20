<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxdpbebte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxdpbebte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-2-fill" /></template>
