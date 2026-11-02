<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsus605jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsus605jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawer-line" /></template>
