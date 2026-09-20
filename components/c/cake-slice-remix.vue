<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owvi75l7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="owvi75l7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cake-slice-remix" /></template>
