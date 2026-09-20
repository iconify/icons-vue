<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcpclgb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcpclgb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:folo-dark" /></template>
