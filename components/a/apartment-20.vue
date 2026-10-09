<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdirvfh-u.css';
import '../../css/r/r60z8bcvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cdirvfh-u"/><path class="r60z8bcvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:apartment-20" /></template>
