<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xomp7-b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xomp7-b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:behance" /></template>
