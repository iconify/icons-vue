<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2bdrrp-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2bdrrp-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:code-line" /></template>
