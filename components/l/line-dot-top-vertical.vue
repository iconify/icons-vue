<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nchdsi1wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nchdsi1wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:line-dot-top-vertical" /></template>
