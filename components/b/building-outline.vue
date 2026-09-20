<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-ho-bbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k-ho-bbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:building-outline" /></template>
