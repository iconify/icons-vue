<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj4b3949s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-6};
const content = `<path class="xj4b3949s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gamepad-retro" /></template>
