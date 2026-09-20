<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_lfds7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3_lfds7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lowcoder-dark" /></template>
