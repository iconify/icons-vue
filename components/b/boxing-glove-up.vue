<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y47lqm_-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y47lqm_-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:boxing-glove-up" /></template>
