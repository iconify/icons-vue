<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf_8a1-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf_8a1-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-2-fill" /></template>
