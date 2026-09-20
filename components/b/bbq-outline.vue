<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeilkf1ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jeilkf1ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bbq-outline" /></template>
