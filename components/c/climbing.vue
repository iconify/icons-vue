<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vko84lncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vko84lncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:climbing" /></template>
