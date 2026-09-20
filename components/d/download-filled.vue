<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnt9_cbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnt9_cbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:download-filled" /></template>
