<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt7buxbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt7buxbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:artboard" /></template>
