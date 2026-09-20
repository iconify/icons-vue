<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql9f2lbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql9f2lbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-long-line" /></template>
