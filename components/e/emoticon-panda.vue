<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxwr1k8hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxwr1k8hq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-panda" /></template>
