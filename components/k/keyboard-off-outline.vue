<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrii360xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrii360xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-off-outline" /></template>
