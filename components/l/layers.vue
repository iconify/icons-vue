<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu9llibef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zu9llibef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layers" /></template>
