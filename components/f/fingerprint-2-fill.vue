<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb2c8cbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb2c8cbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fingerprint-2-fill" /></template>
