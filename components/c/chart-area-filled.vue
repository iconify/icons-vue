<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmweudy3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmweudy3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-area-filled" /></template>
