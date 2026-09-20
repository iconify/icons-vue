<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl-1-hbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl-1-hbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:insert-column-right" /></template>
