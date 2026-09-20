<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd_qk7bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd_qk7bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-light-dimmed" /></template>
