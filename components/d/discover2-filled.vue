<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztg_pfb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztg_pfb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:discover2-filled" /></template>
