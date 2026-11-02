<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks9d45bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9d45bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-2-line" /></template>
