<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owtb_jhsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owtb_jhsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:audio" /></template>
