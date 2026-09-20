<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ru9zb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t8ru9zb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:greek-cross" /></template>
