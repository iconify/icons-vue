<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eftoyqbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eftoyqbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:headphones-with-info-i" /></template>
