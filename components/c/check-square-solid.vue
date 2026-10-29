<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3nyaybuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3nyaybuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-square-solid" /></template>
