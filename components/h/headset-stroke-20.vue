<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_t-mbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="la_t-mbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-stroke-20" /></template>
