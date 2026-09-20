<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_tjgcb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_tjgcb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-waves" /></template>
