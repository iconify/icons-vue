<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx8ltgbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dx8ltgbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hierarchy-5-organize-bold" /></template>
