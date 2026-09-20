<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi-ee_d_q.css';
import '../../css/i/i9aia1bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi-ee_d_q"/><path clip-rule="evenodd" class="i9aia1bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:expressjs" /></template>
