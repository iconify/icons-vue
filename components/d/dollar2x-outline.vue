<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8mmt_bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b8mmt_bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dollar2x-outline" /></template>
