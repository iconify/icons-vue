<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mme4osblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mme4osblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-stroke-20" /></template>
