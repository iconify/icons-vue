<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zle2awbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zle2awbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-bottom-fill" /></template>
