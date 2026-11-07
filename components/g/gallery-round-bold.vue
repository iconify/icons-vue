<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv4_o-byj.css';
import '../../css/w/wzjbfwbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv4_o-byj"/><path clip-rule="evenodd" class="wzjbfwbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-bold" /></template>
