<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxh80fbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh80fbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-switch-filled" /></template>
