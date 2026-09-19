<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki8z8ok4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ki8z8ok4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:caret-up" /></template>
