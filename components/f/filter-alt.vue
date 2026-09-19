<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjcn_pgnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjcn_pgnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:filter-alt" /></template>
