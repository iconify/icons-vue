<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl6wa7bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl6wa7bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lock-open-line" /></template>
