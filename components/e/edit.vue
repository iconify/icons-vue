<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1d9xtb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k1d9xtb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:edit" /></template>
