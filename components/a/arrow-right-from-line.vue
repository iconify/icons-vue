<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfu9pacyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dfu9pacyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-right-from-line" /></template>
