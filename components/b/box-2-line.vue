<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwg7xg3gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwg7xg3gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-2-line" /></template>
