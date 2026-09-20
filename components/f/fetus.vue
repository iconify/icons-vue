<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj58pwuum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uj58pwuum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fetus" /></template>
