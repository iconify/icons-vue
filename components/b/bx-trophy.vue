<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zudnjtb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zudnjtb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-trophy" /></template>
