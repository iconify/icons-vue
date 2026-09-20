<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw1le6i8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw1le6i8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:album-filled" /></template>
