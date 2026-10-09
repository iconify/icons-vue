<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7vk3y3bo.css';
import '../../css/r/rpx2p260d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7vk3y3bo"/><path class="rpx2p260d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:burger-48-bold" /></template>
