<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofsjy_64i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ofsjy_64i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cube-remix" /></template>
