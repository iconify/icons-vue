<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_b8-8a_m.css';
import '../../css/y/ydl-jxb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_b8-8a_m"/><path class="ydl-jxb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:activate-subscriptions-outlined" /></template>
