<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr_sv_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lr_sv_boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-outline-with-star" /></template>
