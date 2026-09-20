<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsp--cbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-8,"top":-7};
const content = `<path class="fsp--cbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header" /></template>
