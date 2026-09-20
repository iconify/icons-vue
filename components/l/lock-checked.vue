<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5r02k1wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5r02k1wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lock-checked" /></template>
