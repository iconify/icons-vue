<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygt2iabqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygt2iabqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-add-fill" /></template>
