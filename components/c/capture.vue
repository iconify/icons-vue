<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytl8wsbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytl8wsbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:capture" /></template>
