<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuzkqezjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuzkqezjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:like-filled" /></template>
