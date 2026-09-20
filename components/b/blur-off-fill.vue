<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwh4_xbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwh4_xbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:blur-off-fill" /></template>
