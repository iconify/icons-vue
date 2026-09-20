<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmgb4967r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pmgb4967r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-pips" /></template>
