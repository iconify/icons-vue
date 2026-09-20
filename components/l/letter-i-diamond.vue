<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_q4f_bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_q4f_bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-diamond" /></template>
