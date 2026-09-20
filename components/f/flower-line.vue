<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp057s9bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp057s9bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-line" /></template>
