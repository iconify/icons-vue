<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l14lsac5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":790};
const content = `<path class="l14lsac5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:basket" /></template>
