<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq-2blb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq-2blb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:leaf-3-line" /></template>
