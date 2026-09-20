<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu2b2g8_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu2b2g8_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:command" /></template>
