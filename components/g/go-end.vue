<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w833t_opg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w833t_opg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:go-end" /></template>
