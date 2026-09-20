<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li_5nlrrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li_5nlrrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code2-filled" /></template>
