<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5jsw1_0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v5jsw1_0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beach-remix" /></template>
