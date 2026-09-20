<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otsew2bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="otsew2bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-power-1-solid" /></template>
