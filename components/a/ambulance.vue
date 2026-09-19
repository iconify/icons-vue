<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6vlwn-dd.css';
import '../../css/x/xmq-usnto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6vlwn-dd"/><path class="xmq-usnto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ambulance" /></template>
