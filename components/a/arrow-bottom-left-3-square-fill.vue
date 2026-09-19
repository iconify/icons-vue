<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lngy86plg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lngy86plg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-3-square-fill" /></template>
