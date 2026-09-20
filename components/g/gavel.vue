<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdj1o0xsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdj1o0xsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gavel" /></template>
