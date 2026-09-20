<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipx_1529y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx_1529y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-heart" /></template>
