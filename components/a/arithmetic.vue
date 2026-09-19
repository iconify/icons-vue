<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enrekdbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="enrekdbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arithmetic" /></template>
