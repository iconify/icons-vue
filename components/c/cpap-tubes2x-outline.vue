<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqzf6mblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wqzf6mblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-tubes2x-outline" /></template>
