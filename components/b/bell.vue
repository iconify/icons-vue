<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chqo5l8nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="chqo5l8nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:bell" /></template>
