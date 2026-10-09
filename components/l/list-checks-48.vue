<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp-dk2bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rp-dk2bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-checks-48" /></template>
