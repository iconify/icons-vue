<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_m1lbgnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_m1lbgnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:fandom-logo-1-block" /></template>
