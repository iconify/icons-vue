<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkmrm2bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkmrm2bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:load" /></template>
