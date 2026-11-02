<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttkikhbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttkikhbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:captions-line" /></template>
