<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahb-vszou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahb-vszou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hood-line" /></template>
