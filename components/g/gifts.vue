<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_nggj52g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o_nggj52g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gifts" /></template>
