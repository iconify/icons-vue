<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgshw4bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgshw4bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-x-solid" /></template>
