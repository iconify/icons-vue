<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6xa-9kku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p6xa-9kku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-beside-car-above-car-beside-car" /></template>
