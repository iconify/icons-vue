<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0xicp_9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0xicp_9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desert" /></template>
