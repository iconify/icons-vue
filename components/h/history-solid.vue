<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqoczpb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqoczpb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:history-solid" /></template>
