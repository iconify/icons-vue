<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr86_qu0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr86_qu0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:add-outline" /></template>
