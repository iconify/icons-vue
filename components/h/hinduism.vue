<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_gxueo7c.css';
import '../../css/p/p6eql6bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_gxueo7c st0"/><path class="p6eql6bly st0"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hinduism" /></template>
