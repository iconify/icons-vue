<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tebc0xb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tebc0xb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:hierarchy-line-3" /></template>
