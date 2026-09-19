<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd22b9x_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pd22b9x_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:forward" /></template>
