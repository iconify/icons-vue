<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0ql8sb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0ql8sb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cro" /></template>
