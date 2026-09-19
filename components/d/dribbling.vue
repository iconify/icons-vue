<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir_2ncbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir_2ncbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dribbling" /></template>
