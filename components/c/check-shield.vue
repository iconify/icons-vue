<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbp_6dbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbp_6dbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:check-shield" /></template>
