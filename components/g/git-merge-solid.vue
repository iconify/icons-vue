<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq73adbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq73adbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-merge-solid" /></template>
