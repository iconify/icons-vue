<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eko1wh1jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eko1wh1jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-2-fill-round" /></template>
