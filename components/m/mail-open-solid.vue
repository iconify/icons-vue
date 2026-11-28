<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_ak76b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ak76b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-open-solid" /></template>
