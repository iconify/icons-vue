<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/binrbta7q.css';
import '../../css/n/nd8dqhb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="binrbta7q"/><path class="nd8dqhb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bitcoin" /></template>
