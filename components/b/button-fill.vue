<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up1nw_wyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up1nw_wyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:button-fill" /></template>
