<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c083e7b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c083e7b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:font-size" /></template>
