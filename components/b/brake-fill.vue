<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp097j4_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp097j4_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brake-fill" /></template>
