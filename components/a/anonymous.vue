<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkj37h9sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xkj37h9sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:anonymous" /></template>
