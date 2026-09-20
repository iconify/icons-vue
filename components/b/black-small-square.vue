<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsiv3aben.css';
import '../../css/q/qta_1ibzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tsiv3aben"/><path class="qta_1ibzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-small-square" /></template>
