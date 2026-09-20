<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpk8_q57l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpk8_q57l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-ink-bold" /></template>
