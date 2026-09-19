<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mim_u7m5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mim_u7m5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adguard" /></template>
