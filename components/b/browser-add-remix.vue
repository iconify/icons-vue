<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1rv31bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k1rv31bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-add-remix" /></template>
