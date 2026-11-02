<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkkp_d1vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkkp_d1vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-2-fill" /></template>
