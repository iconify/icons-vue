<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmdc7ubzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmdc7ubzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:layers-off" /></template>
