<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyognab8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tyognab8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:enzyme" /></template>
