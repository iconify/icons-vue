<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppuipnbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ppuipnbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:city-worker2x-outline" /></template>
