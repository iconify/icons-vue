<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2s-3gbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2s-3gbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-off-line" /></template>
