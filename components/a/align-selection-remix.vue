<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5hlclzjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s5hlclzjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-selection-remix" /></template>
