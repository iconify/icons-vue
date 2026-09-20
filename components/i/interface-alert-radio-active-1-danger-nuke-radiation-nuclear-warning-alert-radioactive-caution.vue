<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykhg1_noq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ykhg1_noq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-alert-radio-active-1-danger-nuke-radiation-nuclear-warning-alert-radioactive-caution" /></template>
