<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw82_714f.css';
import '../../css/y/ysy1t6bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer tw82_714f"/><path class="duoicon-primary-layer ysy1t6bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:camera-square" /></template>
