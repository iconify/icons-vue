<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpbcrv15o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpbcrv15o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-to-bottom-stroke-filled" /></template>
