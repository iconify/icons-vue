<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrlw1ob2d.css';
import '../../css/p/p_titlbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xrlw1ob2d"/><path class="p_titlbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:brokenheart" /></template>
