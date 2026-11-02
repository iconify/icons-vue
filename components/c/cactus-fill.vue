<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_ubp-zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_ubp-zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cactus-fill" /></template>
