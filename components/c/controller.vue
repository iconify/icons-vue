<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdm2j-v_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdm2j-v_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:controller" /></template>
