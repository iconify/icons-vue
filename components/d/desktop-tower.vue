<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f87hdkbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f87hdkbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:desktop-tower" /></template>
