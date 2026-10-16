<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs_50ab_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hs_50ab_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-list-20" /></template>
