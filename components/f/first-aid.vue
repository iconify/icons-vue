<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv_cacb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv_cacb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:first-aid" /></template>
