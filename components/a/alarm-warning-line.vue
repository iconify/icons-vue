<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxoyzrbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxoyzrbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:alarm-warning-line" /></template>
