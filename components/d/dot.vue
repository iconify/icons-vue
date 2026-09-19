<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8nk-ib1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8nk-ib1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dot" /></template>
