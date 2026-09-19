<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct2_n2buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ct2_n2buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:fitness" /></template>
