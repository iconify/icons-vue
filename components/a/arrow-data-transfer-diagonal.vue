<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilq3p7wvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq3p7wvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-data-transfer-diagonal" /></template>
