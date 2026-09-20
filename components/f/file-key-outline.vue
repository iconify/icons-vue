<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnk3k9x0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnk3k9x0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-key-outline" /></template>
