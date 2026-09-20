<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt4_61_lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vt4_61_lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chick" /></template>
