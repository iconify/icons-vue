<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syz0a_bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syz0a_bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-2" /></template>
