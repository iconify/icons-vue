<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_l9mabmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="p_l9mabmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:border-vertical" /></template>
