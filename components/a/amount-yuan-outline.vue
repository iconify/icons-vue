<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_8_z1bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s_8_z1bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-yuan-outline" /></template>
