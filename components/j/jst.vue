<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltz0s7b4l.css';
import '../../css/x/x15y2eb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltz0s7b4l"/><path class="x15y2eb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:jst" /></template>
