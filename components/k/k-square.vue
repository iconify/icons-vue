<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2f2hvbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="k2f2hvbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:k-square" /></template>
