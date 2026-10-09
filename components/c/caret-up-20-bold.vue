<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0lpgpb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t0lpgpb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-up-20-bold" /></template>
