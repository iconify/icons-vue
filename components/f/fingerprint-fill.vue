<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpy5x2bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpy5x2bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-fill" /></template>
