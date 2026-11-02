<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn6s0pb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn6s0pb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-line" /></template>
