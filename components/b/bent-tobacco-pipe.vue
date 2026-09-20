<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqp_ve-xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aqp_ve-xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bent-tobacco-pipe" /></template>
