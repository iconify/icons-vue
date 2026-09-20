<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urhqt-mbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="urhqt-mbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:laptop-project-screen-solid" /></template>
