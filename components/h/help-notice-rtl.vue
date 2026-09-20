<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5w4ir7_r.css';
import '../../css/i/i_mx33b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5w4ir7_r"/><path class="i_mx33b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:help-notice-rtl" /></template>
