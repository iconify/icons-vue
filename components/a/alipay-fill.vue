<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqf-js7hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqf-js7hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alipay-fill" /></template>
