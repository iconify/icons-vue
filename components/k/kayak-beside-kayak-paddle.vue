<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp59d6b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zp59d6b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kayak-beside-kayak-paddle" /></template>
