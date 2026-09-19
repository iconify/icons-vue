<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqer2gnrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqer2gnrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bridges-v1" /></template>
