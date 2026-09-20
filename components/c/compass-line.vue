<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1db94ori.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1db94ori"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compass-line" /></template>
