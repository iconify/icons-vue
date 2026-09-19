<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f82dgl3aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f82dgl3aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:carrot" /></template>
