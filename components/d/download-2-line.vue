<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3s_jfmpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3s_jfmpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-2-line" /></template>
