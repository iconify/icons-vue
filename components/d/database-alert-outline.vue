<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wumm18bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wumm18bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-alert-outline" /></template>
