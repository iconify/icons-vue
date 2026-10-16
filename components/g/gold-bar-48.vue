<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l21du2bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l21du2bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gold-bar-48" /></template>
