<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah0u-xqmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah0u-xqmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circuit-board-solid" /></template>
