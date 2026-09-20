<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp3iq2bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cp3iq2bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-fold-down-left" /></template>
