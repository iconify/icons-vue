<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw9gkzbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nw9gkzbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:lattes" /></template>
