<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpb0-dwzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpb0-dwzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:korean-rectangle-filled" /></template>
