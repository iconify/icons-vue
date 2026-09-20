<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_rkd_or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_rkd_or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:anchor" /></template>
