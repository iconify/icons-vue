<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbue_0b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbue_0b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-alert-solid" /></template>
