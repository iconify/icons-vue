<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofbr-bi5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofbr-bi5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:back-in-time" /></template>
