<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j52f7_bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j52f7_bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copyright-fill" /></template>
