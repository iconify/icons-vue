<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf69wm-ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf69wm-ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dots-horizontal" /></template>
