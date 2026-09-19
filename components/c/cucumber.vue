<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kej-l12dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kej-l12dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cucumber" /></template>
