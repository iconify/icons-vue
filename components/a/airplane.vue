<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa97h8b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xa97h8b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:airplane" /></template>
