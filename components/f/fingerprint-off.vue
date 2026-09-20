<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_-_s0p-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-_s0p-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fingerprint-off" /></template>
