<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcbw_w9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpcbw_w9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:link-2-fill" /></template>
