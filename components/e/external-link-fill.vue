<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyn4ahb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyn4ahb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:external-link-fill" /></template>
