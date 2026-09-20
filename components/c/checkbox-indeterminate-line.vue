<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdp_mqutl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdp_mqutl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-indeterminate-line" /></template>
