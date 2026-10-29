<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebl5rib_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl5rib_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-check-solid" /></template>
