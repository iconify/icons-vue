<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt8s8dbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xt8s8dbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:duck-in-water" /></template>
