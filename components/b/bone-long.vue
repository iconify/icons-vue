<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfshv71lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfshv71lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bone-long" /></template>
