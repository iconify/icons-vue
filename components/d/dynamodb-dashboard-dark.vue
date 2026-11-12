<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd2a3duis.css';
import '../../css/s/sgpjj4b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd2a3duis"/><path class="sgpjj4b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynamodb-dashboard-dark" /></template>
