<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8ws_bxph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8ws_bxph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:box-alt" /></template>
