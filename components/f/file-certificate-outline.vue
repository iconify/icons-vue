<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6d91yjnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6d91yjnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-certificate-outline" /></template>
