<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-f5cn18w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-f5cn18w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:funkwhale-dark" /></template>
