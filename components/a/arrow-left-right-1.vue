<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyj4s-pbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj4s-pbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-right-1" /></template>
