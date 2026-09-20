<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drt20ub7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="drt20ub7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-tray-1" /></template>
