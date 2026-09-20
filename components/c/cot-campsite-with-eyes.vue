<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnab4-blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cnab4-blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cot-campsite-with-eyes" /></template>
