<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phb35-bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phb35-bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:badge-dollar" /></template>
