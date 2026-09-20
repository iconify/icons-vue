<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjr9i_a7v.css';
import '../../css/m/m5y4f8bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="jjr9i_a7v"/><path class="m5y4f8bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:apple-intelligence-frame-line" /></template>
