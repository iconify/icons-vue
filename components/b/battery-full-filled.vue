<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_298ebcy.css';
import '../../css/q/qou13c05m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_298ebcy"/><path class="qou13c05m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:battery-full-filled" /></template>
