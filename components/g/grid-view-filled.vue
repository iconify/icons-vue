<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_08mbc5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_08mbc5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:grid-view-filled" /></template>
