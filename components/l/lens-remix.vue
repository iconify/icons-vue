<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxdr_ubpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxdr_ubpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:lens-remix" /></template>
