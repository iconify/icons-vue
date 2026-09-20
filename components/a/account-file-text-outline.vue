<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bot5o0b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bot5o0b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-file-text-outline" /></template>
