<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giw43fzcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giw43fzcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-up-left" /></template>
