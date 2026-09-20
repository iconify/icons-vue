<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbj4o1-vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbj4o1-vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:link-3-fill" /></template>
