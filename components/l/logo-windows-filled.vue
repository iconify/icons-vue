<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6l8-5blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6l8-5blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-windows-filled" /></template>
