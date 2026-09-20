<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7j8czs5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7j8czs5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-line" /></template>
