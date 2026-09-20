<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czo4g_e8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czo4g_e8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loader-line" /></template>
