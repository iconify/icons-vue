<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prv7dxb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prv7dxb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-3-line" /></template>
