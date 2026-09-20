<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsbw0xb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsbw0xb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-double-se-nw" /></template>
