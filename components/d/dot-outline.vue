<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ki_ab-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k1ki_ab-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dot-outline" /></template>
