<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc-nt5a3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sc-nt5a3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:check" /></template>
