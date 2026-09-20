<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yse773b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yse773b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:imessage-logo" /></template>
