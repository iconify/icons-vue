<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvc44u6gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvc44u6gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bittorrent" /></template>
