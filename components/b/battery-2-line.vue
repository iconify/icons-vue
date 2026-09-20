<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm3pn2bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm3pn2bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-2-line" /></template>
