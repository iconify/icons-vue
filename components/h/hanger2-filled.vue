<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl_d6ch4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl_d6ch4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hanger2-filled" /></template>
