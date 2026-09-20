<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av_0phb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av_0phb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:full-screen-maximize" /></template>
