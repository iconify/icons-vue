<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n72bl5beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n72bl5beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:albums" /></template>
