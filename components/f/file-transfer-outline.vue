<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xads-bcdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xads-bcdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-transfer-outline" /></template>
