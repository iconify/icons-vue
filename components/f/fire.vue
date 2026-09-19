<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh02jbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="bfh02jbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fire" /></template>
