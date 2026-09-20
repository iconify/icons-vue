<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7s_qxalq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7s_qxalq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gitee-fill" /></template>
