<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9xpmoajl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="u9xpmoajl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:input-power" /></template>
