<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thma_ibcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thma_ibcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-off" /></template>
