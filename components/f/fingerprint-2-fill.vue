<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me_w7zb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me_w7zb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-2-fill" /></template>
