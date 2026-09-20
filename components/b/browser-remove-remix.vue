<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1d8i_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oc1d8i_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-remove-remix" /></template>
