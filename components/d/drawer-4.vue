<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcq8hnbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcq8hnbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:drawer-4" /></template>
