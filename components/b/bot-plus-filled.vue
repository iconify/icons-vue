<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yismpnbbv.css';
import '../../css/s/sqh8rebfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path clip-rule="evenodd" class="sqh8rebfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-plus-filled" /></template>
