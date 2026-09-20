<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwj4vccrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iwj4vccrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flower-remix" /></template>
