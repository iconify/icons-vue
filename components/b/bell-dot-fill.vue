<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgmkij3-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xgmkij3-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bell-dot-fill" /></template>
