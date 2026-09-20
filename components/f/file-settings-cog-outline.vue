<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9r_w_bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9r_w_bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-settings-cog-outline" /></template>
