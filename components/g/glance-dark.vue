<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klcg8kbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klcg8kbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glance-dark" /></template>
