<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6qgrrbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p6qgrrbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ladder" /></template>
