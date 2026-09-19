<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2108y1ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":642,"height":717};
const content = `<path class="p2108y1ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:flag" /></template>
