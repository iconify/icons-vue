<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oam8hmbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oam8hmbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bacteria-virus-cells-biology-solid" /></template>
