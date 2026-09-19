<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg1t8_b4v.css';
import '../../css/l/lr3x0vl_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1t8_b4v"/><path class="lr3x0vl_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:food-menu" /></template>
