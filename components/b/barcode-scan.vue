<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asrq_fb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asrq_fb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:barcode-scan" /></template>
