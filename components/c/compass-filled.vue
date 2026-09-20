<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttnu0-bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttnu0-bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:compass-filled" /></template>
