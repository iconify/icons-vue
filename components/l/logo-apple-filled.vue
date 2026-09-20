<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ongrnmbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ongrnmbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-apple-filled" /></template>
