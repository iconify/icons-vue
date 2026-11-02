<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3w_j8_cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3w_j8_cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inbox-line" /></template>
