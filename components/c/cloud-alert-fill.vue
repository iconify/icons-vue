<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpv00lbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpv00lbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-alert-fill" /></template>
