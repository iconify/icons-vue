<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8bfibb-k.css';
import '../../css/b/bkk4-bbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8bfibb-k"/><path class="bkk4-bbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-hospital-building-1" /></template>
