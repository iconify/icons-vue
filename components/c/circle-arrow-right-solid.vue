<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfxe5-btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfxe5-btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-right-solid" /></template>
