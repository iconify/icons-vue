<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng060o56g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ng060o56g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:controller-wireless" /></template>
