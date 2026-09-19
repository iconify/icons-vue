<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqbzzaccj.css';
import '../../css/x/xhcfzkbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sqbzzaccj"/><path class="xhcfzkbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:firewall" /></template>
