<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld2p2fbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld2p2fbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:artboard" /></template>
