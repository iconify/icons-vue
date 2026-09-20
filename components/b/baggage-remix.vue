<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-30giqks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k-30giqks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:baggage-remix" /></template>
