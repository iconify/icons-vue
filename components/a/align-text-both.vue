<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-zz1ta_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-zz1ta_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-text-both" /></template>
