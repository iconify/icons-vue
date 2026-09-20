<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aotl0-zyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aotl0-zyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-left-down" /></template>
