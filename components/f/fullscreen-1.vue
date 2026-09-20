<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3h-12bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3h-12bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fullscreen-1" /></template>
