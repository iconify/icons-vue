<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wemnrpc4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wemnrpc4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-search-corner-fill-round" /></template>
