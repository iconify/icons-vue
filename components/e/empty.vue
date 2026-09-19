<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm3_yrfqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zm3_yrfqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:empty" /></template>
