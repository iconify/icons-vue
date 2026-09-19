<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2_lbuban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t2_lbuban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dash-stroke-12" /></template>
