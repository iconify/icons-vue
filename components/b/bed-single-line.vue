<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzf2re38v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzf2re38v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bed-single-line" /></template>
