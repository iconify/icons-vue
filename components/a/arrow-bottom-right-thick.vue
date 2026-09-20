<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifct9_bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifct9_bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-right-thick" /></template>
