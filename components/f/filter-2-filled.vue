<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz4ladbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="rz4ladbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:filter-2-filled" /></template>
