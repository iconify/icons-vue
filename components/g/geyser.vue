<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ijpj_lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d2ijpj_lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser" /></template>
