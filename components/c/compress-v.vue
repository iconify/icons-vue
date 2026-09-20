<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_on2cm1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_on2cm1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:compress-v" /></template>
