<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrmwqytap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrmwqytap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevron-first-line" /></template>
