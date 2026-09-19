<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xunbskfrx.css';
import '../../css/t/t756e-aqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xunbskfrx"/><path class="t756e-aqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-zip" /></template>
