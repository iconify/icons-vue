<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_gt3b4pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_gt3b4pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cylinder-fill" /></template>
