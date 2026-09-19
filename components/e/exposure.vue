<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk8gf1b0k.css';
import '../../css/x/xtkl7sp6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk8gf1b0k"/><path class="xtkl7sp6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:exposure" /></template>
