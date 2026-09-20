<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uujxc3myq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uujxc3myq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hot-air-balloon-remix" /></template>
