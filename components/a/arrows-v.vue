<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmn2svbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmn2svbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-v" /></template>
