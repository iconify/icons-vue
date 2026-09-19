<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdcpxjb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdcpxjb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-rainy-outline" /></template>
