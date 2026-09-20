<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrp0pi-hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lrp0pi-hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-arrow-up2-filled" /></template>
