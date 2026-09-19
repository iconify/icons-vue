<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1zn45bnx.css';
import '../../css/l/lx2u58bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1zn45bnx"/><path class="lx2u58bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:crypto-filled" /></template>
