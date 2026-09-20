<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux88xgv7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ux88xgv7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jackett-dark" /></template>
