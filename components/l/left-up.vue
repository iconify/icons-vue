<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyqta459c.css';
import '../../css/i/i1nvd4bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyqta459c"/><path class="i1nvd4bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:left-up" /></template>
