<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt14qzb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt14qzb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-1-filled" /></template>
