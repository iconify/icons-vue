<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca-yr3bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ca-yr3bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlen" /></template>
