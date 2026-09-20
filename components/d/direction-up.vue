<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq20hybaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="iq20hybaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:direction-up" /></template>
