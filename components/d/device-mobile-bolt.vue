<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz3l2qr4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz3l2qr4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-bolt" /></template>
