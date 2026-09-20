<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux74nnriu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ux74nnriu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-reaching-down-toward-water" /></template>
