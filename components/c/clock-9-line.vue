<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb6clzb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb6clzb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-9-line" /></template>
