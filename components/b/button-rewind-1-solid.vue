<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhomdvb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhomdvb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-rewind-1-solid" /></template>
