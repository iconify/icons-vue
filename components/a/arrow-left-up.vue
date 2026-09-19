<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ipmzduq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_ipmzduq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arrow-left-up" /></template>
