<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td0cymtxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td0cymtxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-settings-line" /></template>
