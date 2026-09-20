<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddddgibgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddddgibgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-portrait-filled" /></template>
