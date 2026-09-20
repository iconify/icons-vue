<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbxa1bb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wbxa1bb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:library" /></template>
