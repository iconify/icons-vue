<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgs_9lbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pgs_9lbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:graph-circle" /></template>
