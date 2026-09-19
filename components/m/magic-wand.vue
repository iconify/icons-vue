<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okeji4bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okeji4bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:magic-wand" /></template>
