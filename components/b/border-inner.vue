<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiaqwfbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiaqwfbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-inner" /></template>
