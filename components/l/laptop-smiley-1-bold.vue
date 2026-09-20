<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypwzazrln.css';
import '../../css/d/dr7uw4h1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypwzazrln"/><path class="dr7uw4h1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laptop-smiley-1-bold" /></template>
