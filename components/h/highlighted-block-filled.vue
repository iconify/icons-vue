<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjumr4box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjumr4box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:highlighted-block-filled" /></template>
