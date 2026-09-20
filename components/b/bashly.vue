<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss_f9kbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ss_f9kbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:bashly" /></template>
