<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz3dq_b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz3dq_b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-2-fill" /></template>
