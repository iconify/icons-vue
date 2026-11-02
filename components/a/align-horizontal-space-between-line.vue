<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp5j5mbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp5j5mbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-space-between-line" /></template>
