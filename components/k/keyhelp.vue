<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzk41ybbv.css';
import '../../css/x/xgliqgswb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lzk41ybbv"/><path class="xgliqgswb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keyhelp" /></template>
