<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0id_gbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0id_gbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:baseball-bat-ball-bold" /></template>
