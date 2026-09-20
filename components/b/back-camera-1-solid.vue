<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhl62jb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhl62jb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:back-camera-1-solid" /></template>
